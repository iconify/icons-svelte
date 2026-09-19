<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b6y4p5qgt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b6y4p5qgt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:chevron-up-solid" {...props}></Icon>
