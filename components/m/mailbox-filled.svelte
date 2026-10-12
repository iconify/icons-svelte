<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lg8fk_74i.css';
import '../../css/h/hjncjwk0j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lg8fk_74i"/><path clip-rule="evenodd" class="hjncjwk0j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:mailbox-filled" {...props}></Icon>
