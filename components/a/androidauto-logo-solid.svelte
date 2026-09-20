<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/md-b7ezgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="md-b7ezgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:androidauto-logo-solid" {...props}></Icon>
