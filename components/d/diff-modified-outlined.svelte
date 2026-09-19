<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m51-nib4u.css';
import '../../css/g/gp8fatbpd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m51-nib4u"/><circle class="gp8fatbpd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="eos-icons:diff-modified-outlined" {...props}></Icon>
