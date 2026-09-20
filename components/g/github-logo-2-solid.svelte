<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z6s395bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z6s395bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:github-logo-2-solid" {...props}></Icon>
