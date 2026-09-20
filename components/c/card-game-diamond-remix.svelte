<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dzkv1krsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dzkv1krsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:card-game-diamond-remix" {...props}></Icon>
