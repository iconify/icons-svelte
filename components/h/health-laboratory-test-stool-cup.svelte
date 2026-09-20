<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-6wtf2xf.css';
import '../../css/h/h4na1ogqb.css';
import '../../css/y/y7f7bhyxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r-6wtf2xf"/><path class="h4na1ogqb"/><path class="y7f7bhyxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:health-laboratory-test-stool-cup" {...props}></Icon>
