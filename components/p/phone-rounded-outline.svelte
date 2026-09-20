<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cnnb9e_nb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cnnb9e_nb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:phone-rounded-outline" {...props}></Icon>
