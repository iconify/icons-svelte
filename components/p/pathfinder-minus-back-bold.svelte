<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c-6dujoie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c-6dujoie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:pathfinder-minus-back-bold" {...props}></Icon>
