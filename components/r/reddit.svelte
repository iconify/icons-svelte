<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fj67-cbkl.css';
import '../../css/g/gpayj6yuu.css';
import '../../css/o/odhhf9bve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fj67-cbkl"/><path class="gpayj6yuu"/><path class="odhhf9bve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:reddit" {...props}></Icon>
