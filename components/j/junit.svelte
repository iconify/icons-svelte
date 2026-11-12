<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icxtj8y_t.css';
import '../../css/m/m8tseed-k.css';
import '../../css/g/g5loyxbvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="icxtj8y_t"/><path class="m8tseed-k"/><path class="g5loyxbvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:junit" {...props}></Icon>
