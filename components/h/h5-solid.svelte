<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlm0l6bpo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zlm0l6bpo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:h5-solid" {...props}></Icon>
