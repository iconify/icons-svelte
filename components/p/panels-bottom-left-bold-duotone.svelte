<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k408t5b_f.css';
import '../../css/u/u7zit7oth.css';
import '../../css/i/iz-4hbcxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k408t5b_f"/><path class="u7zit7oth"/><path class="iz-4hbcxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-bottom-left-bold-duotone" {...props}></Icon>
