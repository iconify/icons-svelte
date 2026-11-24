<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp17bzlwb.css';
import '../../css/m/m9m_5-b5j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tp17bzlwb"/><path clip-rule="evenodd" class="m9m_5-b5j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:bot-x-filled" {...props}></Icon>
