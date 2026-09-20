<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/he8hc6bkk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="he8hc6bkk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:conda-forge" {...props}></Icon>
