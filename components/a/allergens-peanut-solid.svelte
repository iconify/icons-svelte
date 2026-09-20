<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynao2ccsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ynao2ccsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:allergens-peanut-solid" {...props}></Icon>
