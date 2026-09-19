<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ht_xe9bkp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ht_xe9bkp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:plus-app-fill" {...props}></Icon>
