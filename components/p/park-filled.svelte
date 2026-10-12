<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6riji-tw.css';
import '../../css/t/t05fz5bqy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v6riji-tw"/><path class="t05fz5bqy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:park-filled" {...props}></Icon>
