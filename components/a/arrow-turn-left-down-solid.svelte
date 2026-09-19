<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/egp6p36lg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="egp6p36lg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-left-down-solid" {...props}></Icon>
