<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufey87b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ufey87b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:limesurvey" {...props}></Icon>
