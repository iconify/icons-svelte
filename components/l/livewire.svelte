<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfd2nbe_n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfd2nbe_n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:livewire" {...props}></Icon>
