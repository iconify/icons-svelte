<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnxr3dbjd.css';
import '../../css/n/no6ore_5j.css';
import '../../css/q/qlk7i1b4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bnxr3dbjd"/><path class="no6ore_5j"/><path class="qlk7i1b4e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-ansible-open" {...props}></Icon>
