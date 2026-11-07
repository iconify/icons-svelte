<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ty867ghkp.css';
import '../../css/g/g4e643m4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ty867ghkp"/><path clip-rule="evenodd" class="g4e643m4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:minus-square-outline" {...props}></Icon>
