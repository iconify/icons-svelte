<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kxd_4bb2b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kxd_4bb2b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:roller-paintbrush-remix" {...props}></Icon>
