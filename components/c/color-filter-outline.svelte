<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibmndspam.css';
import '../../css/n/nb7pxabat.css';
import '../../css/d/dwcqehbef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="ibmndspam"/><circle class="nb7pxabat"/><circle class="dwcqehbef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:color-filter-outline" {...props}></Icon>
