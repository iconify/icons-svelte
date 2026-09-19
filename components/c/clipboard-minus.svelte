<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ibu_r4lcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ibu_r4lcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:clipboard-minus" {...props}></Icon>
