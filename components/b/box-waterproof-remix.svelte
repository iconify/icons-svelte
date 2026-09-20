<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fmlo9qb5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fmlo9qb5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:box-waterproof-remix" {...props}></Icon>
