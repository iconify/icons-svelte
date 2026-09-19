<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sebtdl11v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sebtdl11v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-up-right" {...props}></Icon>
