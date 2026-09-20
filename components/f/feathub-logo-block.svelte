<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ndh4a3bpe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ndh4a3bpe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:feathub-logo-block" {...props}></Icon>
