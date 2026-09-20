<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/be98cq8ek.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="be98cq8ek"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:nightstand4" {...props}></Icon>
