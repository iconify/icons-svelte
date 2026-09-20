<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dj09ezbqc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dj09ezbqc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:protractor" {...props}></Icon>
