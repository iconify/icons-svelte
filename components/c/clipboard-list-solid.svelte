<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddqbdrr6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ddqbdrr6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:clipboard-list-solid" {...props}></Icon>
