<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a7kcxrbau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="a7kcxrbau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:chart-radar-filled" {...props}></Icon>
