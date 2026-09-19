<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qucnknb1p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qucnknb1p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:minimize-alt-01" {...props}></Icon>
