<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zw_7llbhm.css';
import '../../css/e/egp4naccw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zw_7llbhm"/><path class="egp4naccw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flat-color-icons:alphabetical-sorting-za" {...props}></Icon>
