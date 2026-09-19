<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ye-jbqbha.css';
import '../../css/f/fzplxusck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ye-jbqbha"/><path clip-rule="evenodd" class="fzplxusck"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:credit-card-filled" {...props}></Icon>
