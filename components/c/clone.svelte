<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hdp245_wj.css';
import '../../css/t/ttyer50st.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":40,"height":40};
const content = `<path class="hdp245_wj"/><path class="ttyer50st"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iwwa:clone" {...props}></Icon>
