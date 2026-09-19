<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/npewmlxrc.css';
import '../../css/u/unp6fccbt.css';
import '../../css/n/na_wzcctt.css';
import '../../css/e/e4sbecbzl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="npewmlxrc"/><path class="unp6fccbt"/><path class="na_wzcctt"/><path class="e4sbecbzl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:diploma-1" {...props}></Icon>
