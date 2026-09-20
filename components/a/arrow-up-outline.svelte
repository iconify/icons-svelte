<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ya9gfz95a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ya9gfz95a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-up-outline" {...props}></Icon>
