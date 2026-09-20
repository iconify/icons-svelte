<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-gq6gbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-gq6gbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:aas-shell-import" {...props}></Icon>
