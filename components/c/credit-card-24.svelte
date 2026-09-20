<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m9mr-b15w.css';
import '../../css/e/ewvinnbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m9mr-b15w"/><path class="ewvinnbde"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:credit-card-24" {...props}></Icon>
