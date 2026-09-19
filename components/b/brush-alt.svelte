<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qb5kezbzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qb5kezbzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:brush-alt" {...props}></Icon>
