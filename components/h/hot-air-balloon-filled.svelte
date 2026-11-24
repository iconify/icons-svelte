<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ynb_ho6fv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ynb_ho6fv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hot-air-balloon-filled" {...props}></Icon>
