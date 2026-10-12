<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n-i7xbe_m.css';
import '../../css/g/g7fuoqbeu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n-i7xbe_m"/><path clip-rule="evenodd" class="g7fuoqbeu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:playing-cards-filled" {...props}></Icon>
