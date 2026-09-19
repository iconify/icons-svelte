<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s98hn0ejv.css';
import '../../css/b/bqbfju-hn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s98hn0ejv"/><path clip-rule="evenodd" class="bqbfju-hn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:node-0-connections-filled" {...props}></Icon>
