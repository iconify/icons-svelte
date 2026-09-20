<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s8-5dqbyl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s8-5dqbyl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dfx" {...props}></Icon>
