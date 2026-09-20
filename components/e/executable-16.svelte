<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zzpz-zbzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="zzpz-zbzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:executable-16" {...props}></Icon>
