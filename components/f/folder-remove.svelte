<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bkqabybbo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkqabybbo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ci:folder-remove" {...props}></Icon>
