<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arncu-41i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="arncu-41i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chef-hat-heart-outline" {...props}></Icon>
