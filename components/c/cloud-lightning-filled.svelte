<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_mguhhan.css';
import '../../css/z/z5f1labnz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f_mguhhan"/><path class="z5f1labnz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:cloud-lightning-filled" {...props}></Icon>
