<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnwq9rb9e.css';
import '../../css/a/ab-wz6bnp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vnwq9rb9e"/><path class="ab-wz6bnp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:database-arrow-up-filled" {...props}></Icon>
