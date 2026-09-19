<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ecejspz5t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ecejspz5t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dog-filled" {...props}></Icon>
