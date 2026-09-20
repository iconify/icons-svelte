<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kb-7nfbwa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kb-7nfbwa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:filter-light" {...props}></Icon>
