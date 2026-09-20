<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/x/xs1dcgb3w.css';
import '../../css/e/ezrebmbjv.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGTJxG6b4E"><g class="ft5dv1b6b"><path class="xs1dcgb3w"/><path class="ezrebmbjv"/></g></mask></defs><path mask="url(#SVGTJxG6b4E)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:home-duotone-line" {...props}></Icon>
