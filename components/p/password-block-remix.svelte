<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/poqrz_5fk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="poqrz_5fk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:password-block-remix" {...props}></Icon>
