<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/djf01d-5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="djf01d-5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:link-solid" {...props}></Icon>
