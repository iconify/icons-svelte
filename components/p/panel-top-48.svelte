<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3q6uacna.css';
import '../../css/l/ls72cy7ht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="v3q6uacna"/><path class="ls72cy7ht"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-top-48" {...props}></Icon>
