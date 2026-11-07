<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r-5ygck_n.css';
import '../../css/e/e_kfhmj_p.css';
import '../../css/i/i2ed-zb3p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r-5ygck_n"/><path class="e_kfhmj_p"/><path clip-rule="evenodd" class="i2ed-zb3p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panels-bottom-right-bold" {...props}></Icon>
