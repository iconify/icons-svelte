<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qzlg7-htb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qzlg7-htb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:cloud-check" {...props}></Icon>
