<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qrj6jqbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qrj6jqbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:non-commercial-dollars-remix" {...props}></Icon>
