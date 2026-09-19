<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/besmmc2bw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="besmmc2bw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:headphones-solid" {...props}></Icon>
