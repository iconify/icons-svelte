<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5he23ykz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="i5he23ykz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:affinity-photo-logo-block" {...props}></Icon>
