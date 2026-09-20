<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvw48nbhb.css';
import '../../css/o/owqh_f_dn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="bvw48nbhb"/><path class="owqh_f_dn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:cloud-up-down-16" {...props}></Icon>
