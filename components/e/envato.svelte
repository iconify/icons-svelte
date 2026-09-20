<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/opp0eqbqw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="opp0eqbqw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:envato" {...props}></Icon>
