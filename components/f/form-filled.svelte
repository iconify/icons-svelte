<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sypqwq-0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sypqwq-0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:form-filled" {...props}></Icon>
