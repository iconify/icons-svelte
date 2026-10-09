<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z55jyj2un.css';
import '../../css/k/kndjxwbkd.css';
import '../../css/i/ijduymbpw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z55jyj2un"/><path class="kndjxwbkd"/><path class="ijduymbpw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:cloud-check-20-bold" {...props}></Icon>
