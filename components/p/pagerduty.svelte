<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hvxma1b7c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvxma1b7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:pagerduty" {...props}></Icon>
