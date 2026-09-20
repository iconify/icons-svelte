<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2exkg4dk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w2exkg4dk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:broadcom-logo-block" {...props}></Icon>
