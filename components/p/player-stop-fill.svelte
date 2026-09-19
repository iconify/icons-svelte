<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itk9nzlcw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="itk9nzlcw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:player-stop-fill" {...props}></Icon>
