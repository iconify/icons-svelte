<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/chd7jkqyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="chd7jkqyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:boxing-glove" {...props}></Icon>
