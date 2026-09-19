<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgd2j9bxg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rgd2j9bxg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-left-up-solid" {...props}></Icon>
