<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d77lg5r_i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d77lg5r_i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:odnoklassniki-logo-block" {...props}></Icon>
