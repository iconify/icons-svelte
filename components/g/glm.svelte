<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7zwcqbda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w7zwcqbda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:glm" {...props}></Icon>
