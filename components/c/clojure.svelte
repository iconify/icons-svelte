<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g8z6qmb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g8z6qmb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="simple-icons:clojure" {...props}></Icon>
