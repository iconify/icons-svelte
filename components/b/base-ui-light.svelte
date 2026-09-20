<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndoljcctl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":24};
const content = `<path class="ndoljcctl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:base-ui-light" {...props}></Icon>
