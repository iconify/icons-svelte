<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3qof8bab.css';
import '../../css/t/tbf2vectn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c3qof8bab"/><path clip-rule="evenodd" class="tbf2vectn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:banknote-x-filled" {...props}></Icon>
