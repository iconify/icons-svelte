<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mu4lqbcsw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mu4lqbcsw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:firefish" {...props}></Icon>
