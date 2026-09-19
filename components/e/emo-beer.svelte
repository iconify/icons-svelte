<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q31__zbib.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1789,"height":1000};
const content = `<path class="q31__zbib"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fontelico:emo-beer" {...props}></Icon>
