<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/ve51lgbsq.css';
import '../../css/d/d2k80oitw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ve51lgbsq"/><path class="d2k80oitw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:bug-twotone" {...props}></Icon>
