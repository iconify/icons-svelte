<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otv6zerrs.css';
import '../../css/x/xqoqyjb5v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<circle class="otv6zerrs"/><circle class="xqoqyjb5v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:record-fill-16" {...props}></Icon>
