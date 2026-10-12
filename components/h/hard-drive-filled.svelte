<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/adkx26buk.css';
import '../../css/e/ex3oebbia.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="adkx26buk"/><path class="ex3oebbia"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:hard-drive-filled" {...props}></Icon>
