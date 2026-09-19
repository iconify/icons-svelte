<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oyqfzub1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="oyqfzub1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:link-broken-alt-02" {...props}></Icon>
