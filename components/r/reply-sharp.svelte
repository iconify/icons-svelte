<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txj5poo9f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txj5poo9f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:reply-sharp" {...props}></Icon>
