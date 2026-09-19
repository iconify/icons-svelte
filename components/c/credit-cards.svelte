<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zav3g9j2t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zav3g9j2t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:credit-cards" {...props}></Icon>
