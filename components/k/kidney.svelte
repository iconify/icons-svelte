<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wu3r8obcb.css';
import '../../css/n/nh9_vbc8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="wu3r8obcb"/><path class="nh9_vbc8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="medical-icon:kidney" {...props}></Icon>
