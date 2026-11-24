<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/di0sukb5w.css';
import '../../css/h/ho6ftnbun.css';
import '../../css/p/pembsco1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="di0sukb5w"/><path class="ho6ftnbun"/><path class="pembsco1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:radio-tower-filled" {...props}></Icon>
