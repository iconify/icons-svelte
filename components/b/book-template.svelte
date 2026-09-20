<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwvjmzyqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cwvjmzyqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:book-template" {...props}></Icon>
