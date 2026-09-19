<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cb4vlibay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cb4vlibay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:dropbox-outline" {...props}></Icon>
