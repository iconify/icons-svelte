<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m0bq-7bdw.css';
import '../../css/j/jc-qmqbqg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m0bq-7bdw"/><path class="jc-qmqbqg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:reader-follow-conversation" {...props}></Icon>
