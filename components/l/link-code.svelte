<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdh645bzz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jdh645bzz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:link-code" {...props}></Icon>
