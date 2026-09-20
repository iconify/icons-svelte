<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kyxqbob-z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kyxqbob-z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:rewind-5-seconds-forward-outline" {...props}></Icon>
