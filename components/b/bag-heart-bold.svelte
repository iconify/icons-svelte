<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca1-ywpud.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ca1-ywpud"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-heart-bold" {...props}></Icon>
