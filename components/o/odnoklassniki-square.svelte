<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nwj_zibxz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1536,"height":1536};
const content = `<path class="nwj_zibxz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:odnoklassniki-square" {...props}></Icon>
