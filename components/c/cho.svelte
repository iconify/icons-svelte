<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp5jgqbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pp5jgqbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cho" {...props}></Icon>
