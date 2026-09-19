<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/da9xnqbfq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="da9xnqbfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:facebook-02" {...props}></Icon>
