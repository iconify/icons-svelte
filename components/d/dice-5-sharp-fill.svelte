<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cwlqg5-8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cwlqg5-8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:dice-5-sharp-fill" {...props}></Icon>
