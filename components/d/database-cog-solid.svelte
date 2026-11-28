<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kw0k5bban.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kw0k5bban"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:database-cog-solid" {...props}></Icon>
