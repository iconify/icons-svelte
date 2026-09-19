<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ul6cc9b9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ul6cc9b9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:fast-forward" {...props}></Icon>
