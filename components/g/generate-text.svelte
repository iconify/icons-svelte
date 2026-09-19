<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/otdkbccyy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="otdkbccyy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:generate-text" {...props}></Icon>
