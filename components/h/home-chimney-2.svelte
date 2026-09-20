<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gtbad5h4g.css';
import '../../css/o/o3c7m2drk.css';
import '../../css/r/rdqn1-b6x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gtbad5h4g"/><path class="o3c7m2drk"/><path class="rdqn1-b6x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:home-chimney-2" {...props}></Icon>
