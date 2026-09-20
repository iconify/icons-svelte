<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v1gg4qb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v1gg4qb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:clock-square" {...props}></Icon>
