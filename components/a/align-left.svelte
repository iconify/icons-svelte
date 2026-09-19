<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tte_n1llm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tte_n1llm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:align-left" {...props}></Icon>
