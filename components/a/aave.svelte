<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz1zejb7f.css';
import '../../css/i/i9lomcmsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zz1zejb7f"/><path class="i9lomcmsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:aave" {...props}></Icon>
